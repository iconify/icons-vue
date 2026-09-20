<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4hh0wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x4hh0wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-drug-medicine" /></template>
