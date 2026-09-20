<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dwkz87bar.css';
import '../../css/a/a8i80jb2p.css';
import '../../css/m/mf_dhvsrk.css';
import '../../css/f/fnjfdobhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dwkz87bar"/><path class="a8i80jb2p"/><path class="mf_dhvsrk"/><path class="fnjfdobhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:globe-filled" /></template>
