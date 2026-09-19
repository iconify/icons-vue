<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mtkkfsbrb.css';
import '../../css/i/iad93baoy.css';
import '../../css/j/jcrlfrbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mtkkfsbrb"/><path clip-rule="evenodd" class="iad93baoy"/><path class="jcrlfrbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bedside-two" /></template>
