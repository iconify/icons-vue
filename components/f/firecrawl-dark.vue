<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za_k_5gja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za_k_5gja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firecrawl-dark" /></template>
