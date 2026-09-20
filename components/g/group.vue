<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nef5l-igr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nef5l-igr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:group" /></template>
