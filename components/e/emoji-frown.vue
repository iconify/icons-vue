<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi4f-hakj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi4f-hakj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-frown" /></template>
