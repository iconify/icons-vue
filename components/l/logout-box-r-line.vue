<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef904ebom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef904ebom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-box-r-line" /></template>
