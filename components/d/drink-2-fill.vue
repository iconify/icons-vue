<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4x8jio_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4x8jio_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drink-2-fill" /></template>
