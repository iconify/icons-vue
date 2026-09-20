<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ly52aibmo.css';
import '../../css/x/xrxaul_zl.css';
import '../../css/d/dv0ekmbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ly52aibmo"/><path class="xrxaul_zl"/><path class="dv0ekmbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:layers" /></template>
