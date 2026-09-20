<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1fe2wnqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":168};
const content = `<path class="h1fe2wnqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cloudinary" /></template>
