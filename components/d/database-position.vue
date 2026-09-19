<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lcee_744z.css';
import '../../css/i/igiiosbvy.css';
import '../../css/q/qm1qe08zp.css';
import '../../css/l/lt7eicu4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="lcee_744z"/><path class="igiiosbvy"/><path class="qm1qe08zp"/><path class="lt7eicu4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:database-position" /></template>
