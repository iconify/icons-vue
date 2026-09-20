<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnu9g8bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dnu9g8bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-up-right-stipple-inner" /></template>
