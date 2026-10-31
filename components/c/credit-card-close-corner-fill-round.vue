<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl96inlcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl96inlcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-close-corner-fill-round" /></template>
