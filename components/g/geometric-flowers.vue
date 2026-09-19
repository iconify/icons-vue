<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lrtadt_mm.css';
import '../../css/p/pmmx72kkg.css';
import '../../css/y/yz9-03dhq.css';
import '../../css/r/ro40x6bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="lrtadt_mm"/><path class="pmmx72kkg"/><path class="yz9-03dhq"/><path class="ro40x6bjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:geometric-flowers" /></template>
