<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8g4cug_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8g4cug_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-minimalistic-bold" /></template>
