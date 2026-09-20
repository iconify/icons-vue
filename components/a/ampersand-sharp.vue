<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu9fh_blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9fh_blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:ampersand-sharp" /></template>
