<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/slojigbta.css';
import '../../css/u/utbznccro.css';
import '../../css/p/pltokbbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="slojigbta"/><path class="utbznccro"/><path class="pltokbbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:beatport-square" /></template>
