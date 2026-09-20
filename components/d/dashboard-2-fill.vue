<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi8c47b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi8c47b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dashboard-2-fill" /></template>
