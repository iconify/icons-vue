<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/siiq3ubdv.css';
import '../../css/m/myyvdnbaf.css';
import '../../css/z/zsubpclpp.css';
import '../../css/a/ag46ix2kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="siiq3ubdv"/><path class="myyvdnbaf wm-a"/><path class="wm-k zsubpclpp"/><path class="ag46ix2kh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-code-sketch" /></template>
