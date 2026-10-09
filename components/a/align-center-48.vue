<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0kc3bl3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d0kc3bl3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-center-48" /></template>
