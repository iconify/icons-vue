<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqnn4pbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iqnn4pbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:diamond-48-bold" /></template>
