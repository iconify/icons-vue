<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slxdrq1zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slxdrq1zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-smile-fill" /></template>
