<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tia2wlril.css';
import '../../css/z/z5rcj_bcz.css';
import '../../css/w/whcbbl0vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="tia2wlril"/><path class="z5rcj_bcz"/><path class="whcbbl0vz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:avocado-one" /></template>
