<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ita-ecckd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q3f8w2f_f.css';
import '../../css/p/pme6y6b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ita-ecckd secondary"/><g class="dt0cm9dhy primary"><path class="q3f8w2f_f"/><path class="pme6y6b3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:backspace-duo" /></template>
