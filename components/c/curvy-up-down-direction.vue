<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp0smd0qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp0smd0qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:curvy-up-down-direction" /></template>
