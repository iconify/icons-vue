<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x52iozflm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x52iozflm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-magnifying-glass" /></template>
