<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3anlkbiz.css';
import '../../css/k/kemupybsm.css';
import '../../css/a/add8lcush.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m3anlkbiz"/><path class="kemupybsm"/><path class="add8lcush"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inspection-20" /></template>
