<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4pwq5s-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4pwq5s-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-d" /></template>
