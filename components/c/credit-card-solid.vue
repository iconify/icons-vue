<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmhh2qtxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmhh2qtxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:credit-card-solid" /></template>
