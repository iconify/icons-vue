<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezyuvccht.css';
import '../../css/l/lz-h06bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ezyuvccht"/><path class="lz-h06bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-pen-20-bold" /></template>
