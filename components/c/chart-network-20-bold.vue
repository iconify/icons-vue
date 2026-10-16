<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd6_1xb5y.css';
import '../../css/x/xo32v0bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dd6_1xb5y"/><path class="xo32v0bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-network-20-bold" /></template>
