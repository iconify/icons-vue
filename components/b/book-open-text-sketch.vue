<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u4i1h5rnw.css';
import '../../css/h/hojxk-buu.css';
import '../../css/m/marbhb1xt.css';
import '../../css/b/bc4_-ymjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u4i1h5rnw"/><path class="hojxk-buu wm-k"/><path class="marbhb1xt wm-k"/><path class="bc4_-ymjz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-text-sketch" /></template>
