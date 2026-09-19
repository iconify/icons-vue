<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hcent-gle.css';
import '../../css/k/kiitlmg0j.css';
import '../../css/h/had8q-s7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hcent-gle"/><path clip-rule="evenodd" class="kiitlmg0j"/><path class="had8q-s7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:building-two" /></template>
