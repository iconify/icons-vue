<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t7oitngpi.css';
import '../../css/h/ho72t4bwy.css';
import '../../css/c/cdzff5bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="t7oitngpi"/><path clip-rule="evenodd" class="ho72t4bwy"/><path class="cdzff5bms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:hamburger" /></template>
