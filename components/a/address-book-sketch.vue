<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hu-l19bkb.css';
import '../../css/i/i0uwx_b1z.css';
import '../../css/v/vc76h5b8i.css';
import '../../css/c/c1313sbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hu-l19bkb"/><path class="i0uwx_b1z wm-a"/><path class="vc76h5b8i wm-k"/><path class="c1313sbwo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:address-book-sketch" /></template>
