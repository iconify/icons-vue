<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/g/grfmi1bfg.css';
import '../../css/p/p08hllbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="h_l78yaxm"/><path class="grfmi1bfg"/><path class="p08hllbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:database-import" /></template>
