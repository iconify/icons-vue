<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qjva00luf.css';
import '../../css/y/ytwl2ebtc.css';
import '../../css/r/rmwzjebkv.css';
import '../../css/e/ez1x61b2a.css';
import '../../css/p/po0yeu5hs.css';
import '../../css/o/ou-u7bcws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qjva00luf"/><path class="ytwl2ebtc"/><path class="rmwzjebkv"/><circle class="ez1x61b2a"/><path class="po0yeu5hs"/><path class="ou-u7bcws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-search-linear" /></template>
