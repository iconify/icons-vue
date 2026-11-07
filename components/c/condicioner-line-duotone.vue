<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mm_litbye.css';
import '../../css/l/l68gd2b_u.css';
import '../../css/u/utklsfbvf.css';
import '../../css/p/piipinbcz.css';
import '../../css/k/kkehyzd5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mm_litbye"/><path class="l68gd2b_u"/><path class="utklsfbvf"/><path class="piipinbcz"/><path class="kkehyzd5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:condicioner-line-duotone" /></template>
