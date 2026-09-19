<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp1d3mbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kp1d3mbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-control" /></template>
