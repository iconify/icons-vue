<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0jy9xbgn.css';
import '../../css/l/l2p99h1gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x0jy9xbgn"/><path class="l2p99h1gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:business-metrics" /></template>
