<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mmzz96bmf.css';
import '../../css/o/o57sxb6nv.css';
import '../../css/r/r8pl9hbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mmzz96bmf"/><path clip-rule="evenodd" class="o57sxb6nv"/><path class="r8pl9hbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery-wide-duotone" /></template>
