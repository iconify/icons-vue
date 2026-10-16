<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2iln_b1i.css';
import '../../css/k/kg_87_b2n.css';
import '../../css/t/t0gjp2bhf.css';
import '../../css/e/ekfibsbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r2iln_b1i"/><path class="kg_87_b2n"/><path class="t0gjp2bhf"/><path class="ekfibsbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airborne-wind-20" /></template>
