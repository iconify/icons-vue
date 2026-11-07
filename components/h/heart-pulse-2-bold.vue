<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glp1ur27k.css';
import '../../css/w/ww5xev0qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glp1ur27k"/><path class="ww5xev0qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-pulse-2-bold" /></template>
