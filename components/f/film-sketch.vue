<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t74_kibuv.css';
import '../../css/j/j33chbdtj.css';
import '../../css/y/yr0n5pb1l.css';
import '../../css/e/et26kmbjm.css';
import '../../css/p/pxmffbcsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t74_kibuv wm-k"/><path class="j33chbdtj wm-k"/><path class="wm-k yr0n5pb1l"/><path class="et26kmbjm wm-a"/><path class="pxmffbcsz wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:film-sketch" /></template>
