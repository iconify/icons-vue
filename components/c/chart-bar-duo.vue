<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pvtarpb7m.css';
import '../../css/s/sukohubkj.css';
import '../../css/w/wa7muobyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pvtarpb7m"/><path class="sukohubkj wm-a"/><path class="wa7muobyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-duo" /></template>
