<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6b4ggwjw.css';
import '../../css/w/wh3bwybmx.css';
import '../../css/q/qimpewblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6b4ggwjw"/><path class="wh3bwybmx"/><path class="qimpewblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-renewable-energy-wind-turbine" /></template>
