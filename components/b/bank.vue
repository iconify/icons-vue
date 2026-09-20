<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rqv1gomtd.css';
import '../../css/t/t0j7vybue.css';
import '../../css/a/aqe47bbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rqv1gomtd"/><path clip-rule="evenodd" class="t0j7vybue"/><path class="aqe47bbrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bank" /></template>
