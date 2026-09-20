<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csbqcrbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csbqcrbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gurobi" /></template>
