<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5fpfqrkj.css';
import '../../css/g/gg61wfd5d.css';
import '../../css/s/s87v5e1do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5fpfqrkj"/><path class="gg61wfd5d"/><path class="s87v5e1do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-health-20" /></template>
