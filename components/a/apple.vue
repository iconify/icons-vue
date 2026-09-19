<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkazs2b4g.css';
import '../../css/r/rms53rbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wkazs2b4g"/><path class="rms53rbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:apple" /></template>
