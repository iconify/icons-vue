<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lgpmj5glp.css';
import '../../css/c/c1pmiebpv.css';
import '../../css/u/ux2n7ervq.css';
import '../../css/j/jlbwv3bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lgpmj5glp"/><circle class="c1pmiebpv"/><path class="ux2n7ervq"/><path class="jlbwv3bdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-2-line-duotone" /></template>
