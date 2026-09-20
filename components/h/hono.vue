<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtmocw91z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtmocw91z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hono" /></template>
