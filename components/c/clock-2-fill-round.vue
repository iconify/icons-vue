<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7is6ubrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7is6ubrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-2-fill-round" /></template>
