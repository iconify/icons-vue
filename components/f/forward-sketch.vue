<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x8n4opbkv.css';
import '../../css/s/sqylgf2bu.css';
import '../../css/b/b_8ozvbnm.css';
import '../../css/v/vv7a3663y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x8n4opbkv"/><path class="sqylgf2bu wm-a"/><path class="b_8ozvbnm wm-k"/><path class="vv7a3663y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:forward-sketch" /></template>
