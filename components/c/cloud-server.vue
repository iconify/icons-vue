<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4r3m-bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4r3m-bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cloud-server" /></template>
