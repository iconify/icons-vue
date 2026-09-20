<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w15e0wb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w15e0wb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:git-merge" /></template>
