<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu5nr2b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu5nr2b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:card-text-sharp" /></template>
