<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wqmw350df.css';
import '../../css/i/i4nmh97zq.css';
import '../../css/g/gy-s2wrwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wqmw350df"/><path class="i4nmh97zq"/><path class="gy-s2wrwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:fried-shrimp" /></template>
