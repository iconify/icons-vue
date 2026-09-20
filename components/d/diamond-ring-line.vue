<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3cra4fap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3cra4fap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:diamond-ring-line" /></template>
