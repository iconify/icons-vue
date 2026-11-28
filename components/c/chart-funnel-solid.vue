<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltl_fpnhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltl_fpnhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-funnel-solid" /></template>
