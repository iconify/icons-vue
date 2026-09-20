<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0nwfviwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0nwfviwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-z" /></template>
