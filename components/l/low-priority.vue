<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si1zmcbxh.css';
import '../../css/f/fvtlxtbin.css';
import '../../css/o/o16hhbcdh.css';
import '../../css/a/akuniccwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="si1zmcbxh"/><g class="fvtlxtbin"><path class="o16hhbcdh"/><path class="akuniccwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:low-priority" /></template>
