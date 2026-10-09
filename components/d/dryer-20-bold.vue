<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmo-gj4um.css';
import '../../css/t/t0j6e-buy.css';
import '../../css/y/y00054bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmo-gj4um"/><path class="t0j6e-buy"/><path class="y00054bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dryer-20-bold" /></template>
