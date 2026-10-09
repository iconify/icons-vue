<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omdaj5bmv.css';
import '../../css/f/fphpswbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omdaj5bmv"/><path class="fphpswbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lithium-48-bold" /></template>
