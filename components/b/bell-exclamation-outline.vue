<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m_508sb5a.css';
import '../../css/e/e4e18qnfm.css';
import '../../css/j/jc5cgnf5h.css';
import '../../css/t/ttzpiac6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="m_508sb5a"/><path clip-rule="evenodd" class="e4e18qnfm"/><path class="jc5cgnf5h"/><path clip-rule="evenodd" class="ttzpiac6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bell-exclamation-outline" /></template>
