<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/btpv9l0sb.css';
import '../../css/l/ly2o3vbnn.css';
import '../../css/e/e4nl4q55e.css';
import '../../css/m/mc4olacnm.css';
import '../../css/x/xmcnbbcza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="btpv9l0sb"/><path class="ly2o3vbnn wm-k"/><path class="e4nl4q55e wm-s"/><path class="mc4olacnm wm-k"/><path class="wm-s xmcnbbcza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-plus-sketch" /></template>
