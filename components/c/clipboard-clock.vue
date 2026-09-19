<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vptemybwm.css';
import '../../css/l/l5t4kvb6g.css';
import '../../css/u/ucje65n3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="vptemybwm"/><path class="l5t4kvb6g"/><path class="ucje65n3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:clipboard-clock" /></template>
