<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbmo2xbmb.css';
import '../../css/r/rp66vlbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbmo2xbmb"/><path class="rp66vlbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:4k" /></template>
