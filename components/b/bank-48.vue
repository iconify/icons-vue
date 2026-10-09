<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8x798baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i8x798baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bank-48" /></template>
