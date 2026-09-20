<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbgvjabpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbgvjabpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-left-2" /></template>
