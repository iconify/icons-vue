<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g-31xg9_q.css';
import '../../css/b/bniz3z8pj.css';
import '../../css/e/e52-lccxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g-31xg9_q"/><path class="bniz3z8pj wm-shadow"/><path class="e52-lccxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:barcode-engrave" /></template>
