<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q46da8bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q46da8bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:credit-card-wireless" /></template>
