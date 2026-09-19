<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/h/hxcf9zb4q.css';
import '../../css/x/xm_53acnr.css';
import '../../css/a/aob06dbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="hxcf9zb4q"/><path class="xm_53acnr"/><rect class="aob06dbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:distribute-horizontal-spacing" /></template>
