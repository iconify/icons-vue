<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ohgw9tnbi.css';
import '../../css/t/t_3s3mbhh.css';
import '../../css/g/gxyr9cctr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ohgw9tnbi"/><path clip-rule="evenodd" class="t_3s3mbhh"/><path class="gxyr9cctr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-2-bold-duotone" /></template>
