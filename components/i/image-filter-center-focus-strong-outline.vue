<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2r6r_wuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2r6r_wuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-filter-center-focus-strong-outline" /></template>
