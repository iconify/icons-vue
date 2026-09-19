<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1wiwabgx.css';
import '../../css/x/xnk1gt9lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q1wiwabgx"/><path class="xnk1gt9lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:file-play" /></template>
