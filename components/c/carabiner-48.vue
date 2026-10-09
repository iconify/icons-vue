<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6_t7vb5q.css';
import '../../css/k/ky_d4sbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6_t7vb5q"/><path class="ky_d4sbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carabiner-48" /></template>
