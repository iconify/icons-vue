<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/pqey3lxda.css';
import '../../css/u/u7hylqbkt.css';
import '../../css/v/vkbnpccsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="pqey3lxda"/><path class="u7hylqbkt"/><path class="vkbnpccsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:afferent-three" /></template>
