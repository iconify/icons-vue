<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu_teqejm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu_teqejm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:arrow-down-right" /></template>
