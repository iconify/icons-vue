<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmo-gj4um.css';
import '../../css/n/n-h74kx_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmo-gj4um"/><path class="n-h74kx_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dishwasher-20-bold" /></template>
