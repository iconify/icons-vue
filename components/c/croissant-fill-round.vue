<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f24fygrjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f24fygrjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:croissant-fill-round" /></template>
