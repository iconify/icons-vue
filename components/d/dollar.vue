<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi1kefnqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi1kefnqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:dollar" /></template>
