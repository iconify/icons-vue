<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xquqyfblz.css';
import '../../css/w/w9t98ac2y.css';
import '../../css/x/xk1bogqxz.css';
import '../../css/b/bwni0_j2d.css';
import '../../css/d/d1up9g-eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xquqyfblz"/><path class="w9t98ac2y wm-a"/><path class="wm-shadow xk1bogqxz"/><path class="bwni0_j2d wm-k"/><path class="d1up9g-eu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hammer-engrave" /></template>
