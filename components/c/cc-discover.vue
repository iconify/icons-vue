<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5t5z5and.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="w5t5z5and"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:cc-discover" /></template>
