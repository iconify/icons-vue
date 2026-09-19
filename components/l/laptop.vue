<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cs4oel9os.css';
import '../../css/o/otz57pxwg.css';
import '../../css/o/osdk9kf8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cs4oel9os"/><path class="otz57pxwg"/><path class="osdk9kf8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:laptop" /></template>
