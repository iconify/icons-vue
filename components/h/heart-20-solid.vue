<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc_t3srcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wc_t3srcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:heart-20-solid" /></template>
