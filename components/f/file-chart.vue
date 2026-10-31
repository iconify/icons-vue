<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kh9nrsbhn.css';
import '../../css/b/bsj4ij2dq.css';
import '../../css/h/hbahlac8l.css';
import '../../css/g/goe2albgd.css';
import '../../css/q/qau95ndpc.css';
import '../../css/c/cnc-a93bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kh9nrsbhn wm-k"/><path class="bsj4ij2dq wm-deco"/><path class="hbahlac8l wm-k"/><path class="goe2albgd wm-k"/><path class="qau95ndpc wm-shadow"/><path class="cnc-a93bb wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:file-chart" /></template>
