<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7qs6qcey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7qs6qcey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:armenian-dram" /></template>
