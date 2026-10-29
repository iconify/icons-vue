<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/juj-yyb3h.css';
import '../../css/r/ryv0a7boy.css';
import '../../css/d/drhbokbsz.css';
import '../../css/n/nu6fsptef.css';
import '../../css/c/ci-xzcbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="juj-yyb3h"/><path class="ryv0a7boy wm-k"/><path class="drhbokbsz wm-a"/><path class="nu6fsptef wm-k"/><path class="ci-xzcbit wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fuel-sketch" /></template>
