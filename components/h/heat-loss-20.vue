<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_v6xgdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rv_v6xgdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-loss-20" /></template>
