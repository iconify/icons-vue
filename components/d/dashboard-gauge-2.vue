<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f25r_yb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f25r_yb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dashboard-gauge-2" /></template>
