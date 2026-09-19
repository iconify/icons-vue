<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzf-ogtqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzf-ogtqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-on-square-stack" /></template>
