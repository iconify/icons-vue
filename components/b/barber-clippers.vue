<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cwxxxccvd.css';
import '../../css/h/hq-54n9xa.css';
import '../../css/g/g0etr6b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cwxxxccvd"/><rect class="hq-54n9xa"/><path class="g0etr6b-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:barber-clippers" /></template>
