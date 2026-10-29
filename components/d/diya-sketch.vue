<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xjo_ygssv.css';
import '../../css/y/yxfrlacge.css';
import '../../css/p/pccmthnzk.css';
import '../../css/r/ri1d2xbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xjo_ygssv"/><path class="wm-a yxfrlacge"/><path class="pccmthnzk wm-k"/><path class="ri1d2xbar wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:diya-sketch" /></template>
