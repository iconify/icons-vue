<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gttixbbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gttixbbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-open-page-variant-outline" /></template>
