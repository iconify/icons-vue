<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uo_jzrbcw.css';
import '../../css/r/rkvs44b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="uo_jzrbcw"/><path clip-rule="evenodd" class="rkvs44b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-0-fill" /></template>
