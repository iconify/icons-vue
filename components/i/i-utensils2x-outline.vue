<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl4crjbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gl4crjbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:i-utensils2x-outline" /></template>
