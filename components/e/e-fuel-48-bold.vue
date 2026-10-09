<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g21_8vbpp.css';
import '../../css/v/v-zb6dbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g21_8vbpp"/><path class="v-zb6dbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-fuel-48-bold" /></template>
