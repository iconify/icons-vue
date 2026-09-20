<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i9a7o5iov.css';
import '../../css/y/ytwl2ebtc.css';
import '../../css/r/rmwzjebkv.css';
import '../../css/d/djtt46btr.css';
import '../../css/p/p_9-p8r6d.css';
import '../../css/o/ou-u7bcws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i9a7o5iov"/><path class="ytwl2ebtc"/><path class="rmwzjebkv"/><path class="djtt46btr"/><path class="p_9-p8r6d"/><path class="ou-u7bcws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-date-linear" /></template>
