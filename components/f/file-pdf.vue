<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l4fbp74nf.css';
import '../../css/a/afd5o-09u.css';
import '../../css/f/fp1e18g4x.css';
import '../../css/q/qbdda2b0i.css';
import '../../css/u/u7l_q6bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l4fbp74nf wm-k"/><path class="afd5o-09u wm-shine"/><path class="fp1e18g4x wm-shine"/><path class="qbdda2b0i wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:file-pdf" /></template>
