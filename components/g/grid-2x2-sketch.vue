<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xpk-u_b6m.css';
import '../../css/n/nq3ku6b8r.css';
import '../../css/c/czpi4dbkk.css';
import '../../css/l/lp9350hqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xpk-u_b6m"/><path class="nq3ku6b8r wm-a"/><path class="czpi4dbkk wm-k"/><path class="lp9350hqv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grid-2x2-sketch" /></template>
