<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a9sqkvb_m.css';
import '../../css/a/a4pwcccxv.css';
import '../../css/x/x4522uhjs.css';
import '../../css/n/nk-54lbig.css';
import '../../css/w/wrkbx9bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a9sqkvb_m wm-k"/><path class="a4pwcccxv wm-shadow"/><path class="wm-k x4522uhjs"/><path class="nk-54lbig wm-k"/><path class="wm-a wrkbx9bny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dna-engrave" /></template>
