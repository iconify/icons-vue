<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/or3g_fb0y.css';
import '../../css/o/o_52rxb2b.css';
import '../../css/w/whx2ksbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="or3g_fb0y"/><path class="o_52rxb2b wm-k"/><path class="whx2ksbdp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-hail-sketch" /></template>
