<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_z-q-bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_z-q-bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:line-chart-line" /></template>
