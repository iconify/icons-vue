<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx_32i24f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx_32i24f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-start-horizontal-sharp" /></template>
