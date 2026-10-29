<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/whqs1q3at.css';
import '../../css/z/zkx0jcb5b.css';
import '../../css/x/xbk20hdgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="whqs1q3at"/><path class="wm-k zkx0jcb5b"/><path class="wm-a xbk20hdgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-stop-sketch" /></template>
