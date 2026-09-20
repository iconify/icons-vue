<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqxyuhbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqxyuhbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:home-analytics-line" /></template>
