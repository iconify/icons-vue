<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2zr55bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2zr55bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-open-outline" /></template>
