<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz02qww4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mz02qww4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-trend-down" /></template>
