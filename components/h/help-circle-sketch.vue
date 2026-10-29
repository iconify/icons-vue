<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hwhho5byv.css';
import '../../css/i/i5h7uqh1e.css';
import '../../css/d/dauhxcish.css';
import '../../css/y/y836pq2wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hwhho5byv"/><path class="i5h7uqh1e wm-a"/><path class="dauhxcish wm-k"/><path class="wm-a y836pq2wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:help-circle-sketch" /></template>
