<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syqutab6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syqutab6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-arrow-up-outline" /></template>
