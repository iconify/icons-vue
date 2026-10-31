<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awoo6h4xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awoo6h4xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-letter-k" /></template>
