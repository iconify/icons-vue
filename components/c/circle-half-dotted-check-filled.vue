<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4mui1gbl.css';
import '../../css/o/o5w1ctb2x.css';
import '../../css/d/d1s63ybjv.css';
import '../../css/v/vwp_5z6gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z4mui1gbl"/><path class="o5w1ctb2x"/><circle class="d1s63ybjv"/><path class="vwp_5z6gf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-half-dotted-check-filled" /></template>
