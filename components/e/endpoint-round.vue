<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/oikz_hy6r.css';
import '../../css/l/ly5956p2q.css';
import '../../css/t/tz4ek_gwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="oikz_hy6r"/><circle class="ly5956p2q"/><path class="tz4ek_gwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:endpoint-round" /></template>
