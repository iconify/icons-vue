<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibunlsb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibunlsb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-to-line-duotone-round" /></template>
