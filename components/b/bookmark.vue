<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc3lr507y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc3lr507y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bookmark" /></template>
