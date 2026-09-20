<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dkacq2k4x.css';
import '../../css/g/gaenu2bgb.css';
import '../../css/g/gp9mhbcvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dkacq2k4x"/><path class="gaenu2bgb"/><path class="gp9mhbcvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:airdrop" /></template>
