<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1nyptb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1nyptb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:checkup-chart-bold" /></template>
