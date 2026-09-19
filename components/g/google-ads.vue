<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jraag1gus.css';
import '../../css/t/tzb2l-bbx.css';
import '../../css/g/g8-jwabbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jraag1gus"/><path class="tzb2l-bbx"/><circle transform="rotate(25 12.083 36.688)" class="g8-jwabbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:google-ads" /></template>
