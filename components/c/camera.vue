<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnnorwv9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":770};
const content = `<path class="jnnorwv9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:camera" /></template>
