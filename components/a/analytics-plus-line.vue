<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx_emh9lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_emh9lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:analytics-plus-line" /></template>
