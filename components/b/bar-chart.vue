<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oifsxdbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oifsxdbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bar-chart" /></template>
