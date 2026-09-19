<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/ayrv02bwd.css';
import '../../css/a/axt9ohbyr.css';
import '../../css/c/cly7zkdlc.css';
import '../../css/n/ncvieabhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="ayrv02bwd"/><circle class="axt9ohbyr"/><path class="cly7zkdlc"/><path class="ncvieabhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:cart-outline" /></template>
