<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8sg5frzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8sg5frzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:gift-shop" /></template>
