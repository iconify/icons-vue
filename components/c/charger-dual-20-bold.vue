<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-b0mlbul.css';
import '../../css/i/i5s91diaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-b0mlbul"/><path class="i5s91diaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-dual-20-bold" /></template>
