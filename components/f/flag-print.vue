<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t12lt_bso.css';
import '../../css/o/opuctyblu.css';
import '../../css/o/omgkgqbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="t12lt_bso"/><path clip-rule="evenodd" class="opuctyblu"/><path clip-rule="evenodd" class="omgkgqbgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:flag-print" /></template>
