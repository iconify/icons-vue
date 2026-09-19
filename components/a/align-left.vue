<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irq1v8bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="irq1v8bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-left" /></template>
