<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zro89qjwt.css';
import '../../css/v/vwrn1bbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zro89qjwt"/><path class="vwrn1bbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-solar-48-bold" /></template>
