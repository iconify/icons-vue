<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ka4w-1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9ka4w-1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:finder-line" /></template>
