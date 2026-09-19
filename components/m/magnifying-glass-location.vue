<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_f3imouw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="k_f3imouw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:magnifying-glass-location" /></template>
