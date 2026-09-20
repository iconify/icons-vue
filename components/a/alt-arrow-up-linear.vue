<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbroeosox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbroeosox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-up-linear" /></template>
