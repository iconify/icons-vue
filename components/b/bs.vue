<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l9ynqqbmy.css';
import '../../css/j/jy_7mhbhw.css';
import '../../css/m/mqzz-ccdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":151};
const content = `<g class="ft5dv1b6b"><path class="l9ynqqbmy"/><path class="jy_7mhbhw"/><path class="mqzz-ccdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:bs" /></template>
