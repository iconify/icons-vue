<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz264vb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz264vb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-h-box" /></template>
