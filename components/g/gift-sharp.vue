<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivtjlcvun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivtjlcvun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gift-sharp" /></template>
