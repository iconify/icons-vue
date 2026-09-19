<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xo540u1dm.css';
import '../../css/i/i75ax53xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<g class="nz_20wbpz"><path class="xo540u1dm"/><path class="i75ax53xw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:kettle" /></template>
