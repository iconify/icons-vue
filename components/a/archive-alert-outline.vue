<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3_f46b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_f46b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-alert-outline" /></template>
