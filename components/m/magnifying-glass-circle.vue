<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1kymxbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1kymxbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:magnifying-glass-circle" /></template>
