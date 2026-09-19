<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4jr_x99l.css';
import '../../css/n/nliu6k9wx.css';
import '../../css/i/ize7wpb1y.css';
import '../../css/x/xustz9bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4jr_x99l"/><path class="nliu6k9wx"/><path class="ize7wpb1y"/><path class="xustz9bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:cell-phone" /></template>
