<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlzxx7u1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlzxx7u1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:lock-sharp" /></template>
