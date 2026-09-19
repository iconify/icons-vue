<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umcw9nm8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="umcw9nm8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dotjs" /></template>
