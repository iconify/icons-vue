<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmacnk1qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmacnk1qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-i-circle" /></template>
