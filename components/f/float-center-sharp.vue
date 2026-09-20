<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li1x4xo6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li1x4xo6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:float-center-sharp" /></template>
