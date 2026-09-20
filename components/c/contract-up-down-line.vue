<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqsfe2ayn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqsfe2ayn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contract-up-down-line" /></template>
