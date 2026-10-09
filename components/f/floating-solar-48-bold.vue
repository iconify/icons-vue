<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxqw9b-rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xxqw9b-rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floating-solar-48-bold" /></template>
