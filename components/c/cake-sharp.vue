<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvj6_sntz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvj6_sntz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cake-sharp" /></template>
