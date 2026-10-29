<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nh0u_v32h.css';
import '../../css/f/fm32n2byj.css';
import '../../css/b/bq6kxj32x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nh0u_v32h"/><path class="fm32n2byj wm-a"/><path class="bq6kxj32x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fish-duo" /></template>
