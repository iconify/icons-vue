<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-_uj7vqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-_uj7vqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gift" /></template>
