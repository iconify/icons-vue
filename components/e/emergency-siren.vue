<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bmuf08bcd.css';
import '../../css/e/e4y_14_tb.css';
import '../../css/i/iroxo5bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bmuf08bcd"/><path clip-rule="evenodd" class="e4y_14_tb"/><path class="iroxo5bfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:emergency-siren" /></template>
