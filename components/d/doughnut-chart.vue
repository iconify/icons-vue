<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuqwgmbol.css';
import '../../css/s/sg2hhebqo.css';
import '../../css/a/ahkvt_bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wuqwgmbol"/><path class="sg2hhebqo"/><path class="ahkvt_bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:doughnut-chart" /></template>
