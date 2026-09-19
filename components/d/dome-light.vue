<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/eb9t03b4i.css';
import '../../css/x/x7sf2z-_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<g class="nz_20wbpz"><path class="eb9t03b4i"/><path class="x7sf2z-_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:dome-light" /></template>
