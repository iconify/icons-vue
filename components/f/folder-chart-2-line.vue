<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh1rvydlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh1rvydlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-chart-2-line" /></template>
