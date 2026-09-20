<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzsx4hbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzsx4hbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-filter-tilt-shift" /></template>
