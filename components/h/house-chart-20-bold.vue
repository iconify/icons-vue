<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmgp-hp4m.css';
import '../../css/u/ufwwjcb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="ufwwjcb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-chart-20-bold" /></template>
