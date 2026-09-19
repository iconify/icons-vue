<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mbiljzlix.css';
import '../../css/o/o2nmueu5h.css';
import '../../css/p/pswfvabxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mbiljzlix"/><path class="o2nmueu5h"/><path class="pswfvabxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:booster-car-seat" /></template>
