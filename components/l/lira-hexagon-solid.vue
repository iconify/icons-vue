<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4e90qb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4e90qb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lira-hexagon-solid" /></template>
