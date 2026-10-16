<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypa03g2ao.css';
import '../../css/c/c0-sywbwt.css';
import '../../css/v/v45g71edj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ypa03g2ao"/><path class="c0-sywbwt"/><path class="v45g71edj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:currency-exchange-48" /></template>
