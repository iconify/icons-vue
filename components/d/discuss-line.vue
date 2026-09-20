<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4280i6sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4280i6sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:discuss-line" /></template>
