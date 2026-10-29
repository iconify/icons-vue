<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qvsrqxb7i.css';
import '../../css/b/bm73mgd1w.css';
import '../../css/x/xrhs2pb-k.css';
import '../../css/a/avrbzj-lo.css';
import '../../css/n/npu7_3byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qvsrqxb7i"/><path class="bm73mgd1w wm-k"/><path class="wm-a xrhs2pb-k"/><path class="avrbzj-lo wm-k"/><path class="npu7_3byv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cooking-pot-sketch" /></template>
