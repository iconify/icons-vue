<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfbaonbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfbaonbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:e-bike-2-fill" /></template>
