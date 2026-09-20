<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_9_dmbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_9_dmbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:float-right-sharp" /></template>
