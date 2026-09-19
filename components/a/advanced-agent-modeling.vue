<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t_ev7s-sv.css';
import '../../css/l/l5y23ru5w.css';
import '../../css/e/egad_2bsg.css';
import '../../css/i/ijh_x_qla.css';
import '../../css/u/ujr09m-6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="t_ev7s-sv"/><g class="l5y23ru5w"><path class="egad_2bsg"/><path class="ijh_x_qla"/><path class="ujr09m-6e"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:advanced-agent-modeling" /></template>
