<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jcs8q1beu.css';
import '../../css/u/uhmo5hb6x.css';
import '../../css/l/lxqcwwbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jcs8q1beu"/><path class="uhmo5hb6x"/><path class="lxqcwwbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:headset-two" /></template>
