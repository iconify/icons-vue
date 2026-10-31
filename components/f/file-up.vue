<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f0ji564to.css';
import '../../css/m/mr740qb7e.css';
import '../../css/l/l-w2okima.css';
import '../../css/i/i5vlfbclw.css';
import '../../css/u/u7l_q6bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f0ji564to wm-k"/><path class="mr740qb7e wm-shine"/><path class="l-w2okima wm-shine"/><path class="i5vlfbclw wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:file-up" /></template>
