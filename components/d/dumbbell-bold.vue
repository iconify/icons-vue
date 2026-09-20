<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d503q0bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d503q0bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-bold" /></template>
