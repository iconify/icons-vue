<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w21zh9bgn.css';
import '../../css/m/mz3iprbbx.css';
import '../../css/a/aypdxigqi.css';
import '../../css/c/cm4lp6e5o.css';
import '../../css/s/swjmkkbck.css';
import '../../css/h/hcn__41dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w21zh9bgn"/><path class="mz3iprbbx"/><path class="aypdxigqi"/><path class="cm4lp6e5o"/><path class="swjmkkbck"/><path class="hcn__41dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:broken-heart" /></template>
