<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke-vqfa8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ke-vqfa8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:adjustments-vertical-20-solid" /></template>
