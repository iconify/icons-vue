<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k83ntuifl.css';
import '../../css/m/maz9ht0sw.css';
import '../../css/y/yxfra0bqr.css';
import '../../css/w/we3m-pbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k83ntuifl"/><path class="maz9ht0sw"/><path class="yxfra0bqr"/><path class="we3m-pbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:export-cable-20" /></template>
