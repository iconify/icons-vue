<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f3p-g4m6q.css';
import '../../css/s/smcsc6bgv.css';
import '../../css/q/q661scbjc.css';
import '../../css/b/bkya-ccdx.css';
import '../../css/h/hpzuy57gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f3p-g4m6q"/><path class="smcsc6bgv"/><path class="q661scbjc"/><path class="bkya-ccdx"/><path class="hpzuy57gm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:jar-of-pills-broken" /></template>
