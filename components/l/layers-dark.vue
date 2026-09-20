<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iebp_9cqm.css';
import '../../css/i/ilr4rab5a.css';
import '../../css/a/a4bu9h0na.css';
import '../../css/p/pskf2nb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="iebp_9cqm"><path class="ilr4rab5a"/><path class="a4bu9h0na"/><path class="pskf2nb6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:layers-dark" /></template>
