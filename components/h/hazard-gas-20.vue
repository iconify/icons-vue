<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6_s1zkbf.css';
import '../../css/j/jgob_eb-m.css';
import '../../css/o/oonsc9nwe.css';
import '../../css/d/dijq8qbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="jgob_eb-m"/><path class="oonsc9nwe"/><path class="dijq8qbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-gas-20" /></template>
