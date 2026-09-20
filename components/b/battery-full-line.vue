<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fll4_tu9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fll4_tu9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:battery-full-line" /></template>
