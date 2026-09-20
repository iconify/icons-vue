<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx5x3u-1w.css';
import '../../css/u/u7gqq6bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mx5x3u-1w"/><path class="u7gqq6bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-fish-bone" /></template>
