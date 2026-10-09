<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2_zy01_l.css';
import '../../css/u/uvhzmp04b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r2_zy01_l"/><path class="uvhzmp04b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-bus-20" /></template>
