<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3fj33wpt.css';
import '../../css/i/ihm7jy0xh.css';
import '../../css/m/mzh_2zvez.css';
import '../../css/q/qbnjm1-8j.css';
import '../../css/k/kpd7u-cql.css';
import '../../css/r/rue2fbori.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3fj33wpt"/><path class="ihm7jy0xh"/><path class="mzh_2zvez"/><path class="qbnjm1-8j"/><path class="kpd7u-cql"/><path class="rue2fbori"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kitsu" /></template>
