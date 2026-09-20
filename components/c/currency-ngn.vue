<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih8l9kbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih8l9kbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-ngn" /></template>
