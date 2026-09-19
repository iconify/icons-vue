<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/homst6gcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="homst6gcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:arrow-right" /></template>
