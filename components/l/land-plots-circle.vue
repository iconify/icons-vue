<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ev1iyet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-ev1iyet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:land-plots-circle" /></template>
