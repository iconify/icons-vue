<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb6b0ugaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb6b0ugaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bar-chart-2-fill" /></template>
