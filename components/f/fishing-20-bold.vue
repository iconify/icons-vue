<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlu1ghlpb.css';
import '../../css/r/run42fbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mlu1ghlpb"/><path class="run42fbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fishing-20-bold" /></template>
