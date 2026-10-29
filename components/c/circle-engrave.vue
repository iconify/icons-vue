<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c0vt6ucws.css';
import '../../css/d/dge-srbqq.css';
import '../../css/f/fp8z02naw.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/z/z5ocxlbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c0vt6ucws wm-k"/><path class="dge-srbqq wm-a"/><path class="fp8z02naw wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="wm-a z5ocxlbvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-engrave" /></template>
