<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs4vcfb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs4vcfb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-center-vertical" /></template>
