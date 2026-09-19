<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jf4xiob2j.css';
import '../../css/g/gpcy8vslv.css';
import '../../css/i/in_9y-pym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jf4xiob2j"/><rect class="gpcy8vslv"/><path class="in_9y-pym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:beauty-instrument" /></template>
