<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vdpoyrbwh.css';
import '../../css/t/t98__9s6v.css';
import '../../css/i/iru-mbbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="vdpoyrbwh"/><circle class="t98__9s6v"/><path class="iru-mbbdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:address-book" /></template>
