<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dirz042nc.css';
import '../../css/x/xdy3g3xzv.css';
import '../../css/t/tihjbyfia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dirz042nc"/><path class="xdy3g3xzv"/><path class="tihjbyfia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-off-broken" /></template>
