<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na7e-6bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na7e-6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-ring-outline" /></template>
