<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqd7_actr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqd7_actr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-check-corner-round" /></template>
