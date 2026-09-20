<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0j17oawz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0j17oawz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrow-right-arrow-left" /></template>
