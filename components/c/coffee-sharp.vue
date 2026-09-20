<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7i1zbxps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7i1zbxps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:coffee-sharp" /></template>
