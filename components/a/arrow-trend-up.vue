<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj5x8lblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wj5x8lblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-trend-up" /></template>
