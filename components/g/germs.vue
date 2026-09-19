<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rr9p5hlao.css';
import '../../css/e/eir-cobpl.css';
import '../../css/v/v-ax0bbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rr9p5hlao"/><path class="eir-cobpl"/><path class="v-ax0bbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:germs" /></template>
