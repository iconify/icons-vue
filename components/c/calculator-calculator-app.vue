<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tq557m70x.css';
import '../../css/p/ptbcjcfqf.css';
import '../../css/c/cvihrobuv.css';
import '../../css/s/s8efgpcwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tq557m70x"/><path class="ptbcjcfqf"/><path class="cvihrobuv"/><path class="s8efgpcwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:calculator-calculator-app" /></template>
