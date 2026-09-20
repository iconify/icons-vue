<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jgun0ccrs.css';
import '../../css/y/ytwl2ebtc.css';
import '../../css/r/rmwzjebkv.css';
import '../../css/u/ue-h37-nb.css';
import '../../css/t/tv6qiybum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jgun0ccrs"/><path class="ytwl2ebtc"/><path class="rmwzjebkv"/><path class="ue-h37-nb"/><path class="tv6qiybum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-add-broken" /></template>
