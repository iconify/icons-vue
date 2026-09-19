<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/i_v32wbmb.css';
import '../../css/r/rd65jodhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><path class="i_v32wbmb"/><path class="rd65jodhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cc" /></template>
