<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz7_i0dqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz7_i0dqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dashboard-horizontal-fill" /></template>
