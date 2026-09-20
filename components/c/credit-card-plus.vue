<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym9ljfbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym9ljfbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:credit-card-plus" /></template>
