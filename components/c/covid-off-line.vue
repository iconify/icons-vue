<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miu5gabev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miu5gabev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:covid-off-line" /></template>
