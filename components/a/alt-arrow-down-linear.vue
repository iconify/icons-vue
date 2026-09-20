<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx6v7i57h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx6v7i57h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-down-linear" /></template>
