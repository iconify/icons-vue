<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xie0vpbck.css';
import '../../css/r/rp66vlbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xie0vpbck"/><path class="rp66vlbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:closed-caption" /></template>
