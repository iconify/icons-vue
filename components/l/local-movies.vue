<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdd-yccal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="kdd-yccal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-movies" /></template>
