<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hhhhlpzei.css';
import '../../css/i/i1m49fb9a.css';
import '../../css/g/gsc2_-cfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hhhhlpzei"/><path class="i1m49fb9a"/><path class="gsc2_-cfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:delivery" /></template>
