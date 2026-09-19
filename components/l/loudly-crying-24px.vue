<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nuj_w_oqv.css';
import '../../css/g/gvu5g0xzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nuj_w_oqv"/><path clip-rule="evenodd" class="gvu5g0xzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:loudly-crying-24px" /></template>
