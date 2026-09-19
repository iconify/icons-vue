<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mqxji9yws.css';
import '../../css/o/otvmc61gw.css';
import '../../css/n/ngxz40b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mqxji9yws"/><path clip-rule="evenodd" class="otvmc61gw"/><path class="ngxz40b9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:calculator-print" /></template>
