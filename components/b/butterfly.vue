<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/d9e5_wzxb.css';
import '../../css/h/hvz5n6bel.css';
import '../../css/g/gn6ol4bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="d9e5_wzxb"/><path class="hvz5n6bel"/><path class="gn6ol4bzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:butterfly" /></template>
