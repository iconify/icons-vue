<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lmla34nnh.css';
import '../../css/s/stk13fbal.css';
import '../../css/s/suvv_lbra.css';
import '../../css/n/ni2pyrbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lmla34nnh wm-k"/><path class="stk13fbal wm-a"/><path class="suvv_lbra wm-k"/><path class="ni2pyrbla wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fan-sketch" /></template>
