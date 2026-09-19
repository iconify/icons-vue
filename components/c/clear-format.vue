<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/g/gsx1bnbse.css';
import '../../css/s/sul83f9ve.css';
import '../../css/o/obbrti2nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="h01tyzbfu"><path class="gsx1bnbse"/><path class="sul83f9ve"/><path class="obbrti2nr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:clear-format" /></template>
