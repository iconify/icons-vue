<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e13-6lb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e13-6lb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-minimalistic-linear" /></template>
