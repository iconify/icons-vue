<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0gxl0bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d0gxl0bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-right-48" /></template>
