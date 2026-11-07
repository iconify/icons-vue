<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um1bj7bbr.css';
import '../../css/g/gph3mkbfr.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/d/d_5l10bed.css';
import '../../css/n/n4ivllbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um1bj7bbr"/><path class="gph3mkbfr"/><g class="xtpeb-edw"><path class="d_5l10bed"/><path class="n4ivllbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightning-bold-duotone" /></template>
