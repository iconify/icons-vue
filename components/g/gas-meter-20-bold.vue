<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbys_lb8n.css';
import '../../css/y/ykkgrkb-l.css';
import '../../css/d/d-kptbbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbys_lb8n"/><path class="ykkgrkb-l"/><path class="d-kptbbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-meter-20-bold" /></template>
