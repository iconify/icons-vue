<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k66w0-bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k66w0-bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:apple-vision-pro" /></template>
