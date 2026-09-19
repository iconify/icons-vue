<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/ndb7b7lyp.css';
import '../../css/j/jcjjd5bjf.css';
import '../../css/g/gxdryjbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ndb7b7lyp"/><path class="jcjjd5bjf"/><path class="gxdryjbrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:add-item" /></template>
