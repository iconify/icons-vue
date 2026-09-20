<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n0_shybnl.css';
import '../../css/v/vwwyiacly.css';
import '../../css/u/urwe8bb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n0_shybnl"/><path class="vwwyiacly"/><path class="urwe8bb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-broken" /></template>
