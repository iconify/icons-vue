<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qivazt3xq.css';
import '../../css/h/hwkz_mbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qivazt3xq"/><path class="hwkz_mbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:control-panel" /></template>
