<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3_apj8zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_apj8zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-sort-ascending" /></template>
