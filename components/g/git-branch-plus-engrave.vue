<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nm3w18p8d.css';
import '../../css/w/wo5v4_8xt.css';
import '../../css/k/kpjz0wblu.css';
import '../../css/u/u4synlg4b.css';
import '../../css/c/cd-6u1e9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nm3w18p8d wm-k"/><path class="wm-s wo5v4_8xt"/><path class="kpjz0wblu wm-shadow"/><path class="u4synlg4b wm-k"/><path class="cd-6u1e9y wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-plus-engrave" /></template>
