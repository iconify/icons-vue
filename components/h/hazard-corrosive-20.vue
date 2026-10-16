<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6_s1zkbf.css';
import '../../css/c/cyt56vxcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="cyt56vxcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-corrosive-20" /></template>
