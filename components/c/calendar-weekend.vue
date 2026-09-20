<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz69eqhxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz69eqhxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-weekend" /></template>
