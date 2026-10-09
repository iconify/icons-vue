<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eog_imuls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eog_imuls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floating-solar-48" /></template>
