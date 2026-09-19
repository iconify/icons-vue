<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5q6tg5iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r5q6tg5iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-arrow-down-20-solid" /></template>
