<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/orqm88b8k.css';
import '../../css/f/fhyknpbnv.css';
import '../../css/z/zr0h6scca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="orqm88b8k"/><path class="fhyknpbnv"/><path class="zr0h6scca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hair-dryer" /></template>
