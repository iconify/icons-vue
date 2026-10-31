<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5cl3acyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5cl3acyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-sparkle-fill-round" /></template>
