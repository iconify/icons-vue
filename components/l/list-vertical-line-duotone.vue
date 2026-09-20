<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gy2469b1p.css';
import '../../css/u/u29udfb1o.css';
import '../../css/j/jgx5nz-xl.css';
import '../../css/r/r9gp_ab3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gy2469b1p"/><path class="u29udfb1o"/><path class="jgx5nz-xl"/><path class="r9gp_ab3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-vertical-line-duotone" /></template>
