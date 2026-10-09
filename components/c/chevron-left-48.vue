<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moelc-t-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moelc-t-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-left-48" /></template>
