<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wws_a7ftb.css';
import '../../css/n/nlzn_o26i.css';
import '../../css/u/uu38agbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wws_a7ftb"/><path class="nlzn_o26i"/><path class="uu38agbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:box-20-bold" /></template>
