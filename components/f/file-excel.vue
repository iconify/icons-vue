<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/w0j83f0iw.css';
import '../../css/m/mh46jehah.css';
import '../../css/t/tabomebrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="w0j83f0iw"/><path class="mh46jehah"/><path class="tabomebrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:file-excel" /></template>
