<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/des5-xb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="des5-xb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gift-of-knowledge" /></template>
