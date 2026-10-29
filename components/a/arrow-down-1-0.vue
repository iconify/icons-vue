<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8gq40bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8gq40bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-1-0" /></template>
