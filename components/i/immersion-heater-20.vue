<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2k6suboh.css';
import '../../css/w/wsn4cdbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d2k6suboh"/><path class="wsn4cdbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:immersion-heater-20" /></template>
