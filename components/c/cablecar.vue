<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww_sytbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ww_sytbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cablecar" /></template>
