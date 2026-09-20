<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo3byjb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo3byjb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:earth-sphere-line" /></template>
