<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kpg7scfkl.css';
import '../../css/h/hv1_qk9jj.css';
import '../../css/m/mjecvc15l.css';
import '../../css/g/gfqmenbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kpg7scfkl"/><path class="hv1_qk9jj wm-a"/><path class="mjecvc15l"/><path class="gfqmenbgk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:axe-duo" /></template>
