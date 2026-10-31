<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khunfubsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khunfubsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-sparkle-fill-round" /></template>
