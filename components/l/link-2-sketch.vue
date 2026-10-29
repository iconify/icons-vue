<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n53wu2b_e.css';
import '../../css/r/r5laay04u.css';
import '../../css/p/pqmcw-4da.css';
import '../../css/m/mfyydnb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n53wu2b_e wm-k"/><path class="r5laay04u wm-a"/><path class="pqmcw-4da wm-k"/><path class="mfyydnb2b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:link-2-sketch" /></template>
