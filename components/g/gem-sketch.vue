<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xg0j9x26e.css';
import '../../css/b/blft1cbon.css';
import '../../css/c/clf6vsb1b.css';
import '../../css/x/xhd5x_bfq.css';
import '../../css/m/mb2lklbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xg0j9x26e"/><path class="blft1cbon wm-k"/><path class="clf6vsb1b wm-a"/><path class="wm-k xhd5x_bfq"/><path class="mb2lklbxi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gem-sketch" /></template>
