<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5lo8smcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5lo8smcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cloud-arrow-up" /></template>
