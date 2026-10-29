<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tbzm2gqcw.css';
import '../../css/w/w_jb_zbpr.css';
import '../../css/l/lr0oojb-x.css';
import '../../css/s/sciz89bxj.css';
import '../../css/v/v8bcv9g6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tbzm2gqcw"/><path class="w_jb_zbpr wm-k"/><path class="lr0oojb-x wm-a"/><path class="sciz89bxj wm-k"/><path class="v8bcv9g6a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-stack-sketch" /></template>
