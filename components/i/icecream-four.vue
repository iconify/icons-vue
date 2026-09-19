<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/c5xlswnoj.css';
import '../../css/t/tb7bjd3vj.css';
import '../../css/a/aovl4bbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="c5xlswnoj"/><path class="tb7bjd3vj"/><path class="aovl4bbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:icecream-four" /></template>
