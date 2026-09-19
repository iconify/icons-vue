<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d77g6mbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="d77g6mbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:deviantart" /></template>
