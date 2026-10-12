<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bwu4h-brz.css';
import '../../css/w/w_n6d5bjy.css';
import '../../css/q/qg2o_4obj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bwu4h-brz"/><path class="w_n6d5bjy"/><path class="qg2o_4obj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bottle-wine-duotone" /></template>
