<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-f1gczsv.css';
import '../../css/t/toa-48bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-f1gczsv"/><path class="toa-48bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:account" /></template>
