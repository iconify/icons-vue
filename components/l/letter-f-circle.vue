<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-h9fkyoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-h9fkyoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-f-circle" /></template>
