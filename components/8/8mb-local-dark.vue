<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8f3r6nli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8f3r6nli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:8mb-local-dark" /></template>
