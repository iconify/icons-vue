<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs5dpr2nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="rs5dpr2nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:funnel" /></template>
