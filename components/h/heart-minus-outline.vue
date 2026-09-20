<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufn91ebbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufn91ebbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-minus-outline" /></template>
