<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t0dw4ybam.css';
import '../../css/s/sad7sib5y.css';
import '../../css/f/fgkc19bpy.css';
import '../../css/e/euhc06b6i.css';
import '../../css/r/r309anzoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t0dw4ybam wm-k"/><path class="sad7sib5y wm-a"/><path class="fgkc19bpy wm-shadow"/><path class="euhc06b6i wm-k"/><path class="r309anzoi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:building-engrave" /></template>
