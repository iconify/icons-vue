<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep1rdvbyo.css';
import '../../css/n/n6y0u1blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ep1rdvbyo"/><path class="n6y0u1blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floor-plan-20" /></template>
