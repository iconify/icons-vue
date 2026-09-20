<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htvyfdo4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htvyfdo4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:drawing-compass-solid" /></template>
