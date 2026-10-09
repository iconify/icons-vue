<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz8vwp2ry.css';
import '../../css/y/y854psd3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yz8vwp2ry"/><path class="y854psd3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gear-20-bold" /></template>
