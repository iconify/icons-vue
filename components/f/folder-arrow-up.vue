<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi124rbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi124rbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-arrow-up" /></template>
