<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxth97d7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxth97d7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:covid-exclamation-line" /></template>
