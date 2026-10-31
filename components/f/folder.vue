<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hjy3d14_j.css';
import '../../css/i/iwcskgmvs.css';
import '../../css/e/e_wos8bnc.css';
import '../../css/c/coid4cp1e.css';
import '../../css/k/khsgn_b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hjy3d14_j wm-k"/><path class="iwcskgmvs wm-shine"/><path class="e_wos8bnc wm-shine"/><path class="coid4cp1e wm-shine"/><path class="khsgn_b9w wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:folder" /></template>
