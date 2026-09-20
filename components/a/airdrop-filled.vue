<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ldnjy29ps.css';
import '../../css/n/nv9013mnf.css';
import '../../css/k/ksnd1ac_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ldnjy29ps"/><path class="nv9013mnf"/><path class="ksnd1ac_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:airdrop-filled" /></template>
