<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/istg6zbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="istg6zbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:import-line" /></template>
