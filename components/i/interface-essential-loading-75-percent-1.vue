<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbq02_gxn.css';
import '../../css/q/qlu-mbtpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xbq02_gxn"/><path class="qlu-mbtpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-75-percent-1" /></template>
