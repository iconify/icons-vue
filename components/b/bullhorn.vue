<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0vix41sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0vix41sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:bullhorn" /></template>
