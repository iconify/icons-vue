<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sulnyibag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sulnyibag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-fast-outline" /></template>
