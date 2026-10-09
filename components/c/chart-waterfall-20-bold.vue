<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8r44id8f.css';
import '../../css/n/n-7_zw30i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u8r44id8f"/><path class="n-7_zw30i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-waterfall-20-bold" /></template>
