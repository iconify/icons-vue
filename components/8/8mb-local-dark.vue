<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc6q_garz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cc6q_garz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:8mb-local-dark" /></template>
