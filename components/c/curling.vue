<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dpzbtra.css';
import '../../css/b/ble3jubnc.css';
import '../../css/s/shz9zobhz.css';
import '../../css/r/r4tcq2bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="ble3jubnc"/><path class="shz9zobhz"/><path class="r4tcq2bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:curling" /></template>
