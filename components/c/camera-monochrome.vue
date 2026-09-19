<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmrc5cb8g.css';
import '../../css/o/oc2xyccjk.css';
import '../../css/v/vgo5klasq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmrc5cb8g"/><path class="oc2xyccjk"/><path class="vgo5klasq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-monochrome" /></template>
