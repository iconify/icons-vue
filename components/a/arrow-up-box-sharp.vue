<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1qd13b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1qd13b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-up-box-sharp" /></template>
