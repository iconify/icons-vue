<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ue5yfeb0t.css';
import '../../css/q/qda327bnf.css';
import '../../css/o/ot7ug_ubs.css';
import '../../css/e/e_jnf7h6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ue5yfeb0t wm-k"/><path class="qda327bnf wm-shadow"/><path class="ot7ug_ubs wm-k"/><path class="e_jnf7h6d wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:croissant-engrave" /></template>
