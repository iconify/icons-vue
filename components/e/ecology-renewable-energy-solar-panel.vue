<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zknv2ormj.css';
import '../../css/v/vnc6qjvvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zknv2ormj"/><path class="vnc6qjvvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-renewable-energy-solar-panel" /></template>
