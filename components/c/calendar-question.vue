<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovlb1y99d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovlb1y99d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-question" /></template>
