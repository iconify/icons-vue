<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af8ldbcpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af8ldbcpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:e-bike-2-line" /></template>
