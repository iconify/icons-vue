<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3u8slx_m.css';
import '../../css/f/f7t-e2bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3u8slx_m"/><path class="f7t-e2bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-stream-reference" /></template>
