<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pjoarub1b.css';
import '../../css/z/zxnyw2byw.css';
import '../../css/g/gkgzykt4b.css';
import '../../css/f/fyvo1qg6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pjoarub1b wm-deco"/><path class="wm-k zxnyw2byw"/><path class="gkgzykt4b wm-k"/><path class="fyvo1qg6w wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jalebi-sketch" /></template>
