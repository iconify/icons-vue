<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8nlrybbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8nlrybbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:brackets-content-sharp" /></template>
