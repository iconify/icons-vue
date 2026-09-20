<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8y2g1w-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8y2g1w-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-variant-off-outline" /></template>
