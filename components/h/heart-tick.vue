<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/ket9b_brq.css';
import '../../css/i/irpq6_opq.css';
import '../../css/n/nu1vehbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ket9b_brq"/><path class="irpq6_opq"/><path class="nu1vehbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-tick" /></template>
