<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sol21dz1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sol21dz1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-days-fill-round" /></template>
