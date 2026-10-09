<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiuahbcqc.css';
import '../../css/n/nri5-qgzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qiuahbcqc"/><path class="nri5-qgzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:depot-charging-20-bold" /></template>
