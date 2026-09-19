<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g--kdaczh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g--kdaczh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:heart-half-outline" /></template>
