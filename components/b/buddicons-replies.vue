<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd4_62byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fd4_62byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-replies" /></template>
