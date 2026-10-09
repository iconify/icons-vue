<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-0u-abei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-0u-abei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-center-20" /></template>
