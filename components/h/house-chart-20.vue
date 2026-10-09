<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7juawdew.css';
import '../../css/x/x_jd0jbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="x_jd0jbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-chart-20" /></template>
