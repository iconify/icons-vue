<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxbp-8bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxbp-8bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-grid-line" /></template>
