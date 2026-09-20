<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/far2fhbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="far2fhbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:box-2-line" /></template>
