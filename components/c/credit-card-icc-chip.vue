<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8f83c8eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8f83c8eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-icc-chip" /></template>
