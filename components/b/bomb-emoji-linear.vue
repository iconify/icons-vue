<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/m/m8po4lb0y.css';
import '../../css/d/dg7kedy1c.css';
import '../../css/u/ux6s2nbnw.css';
import '../../css/w/ws_nvmbfy.css';
import '../../css/k/k0xylug1p.css';
import '../../css/t/tsz6qlbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="m8po4lb0y"/><path class="dg7kedy1c"/><path class="ux6s2nbnw"/><path class="ws_nvmbfy"/><path class="k0xylug1p"/><ellipse class="tsz6qlbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-emoji-linear" /></template>
