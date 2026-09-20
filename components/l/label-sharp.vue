<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te6ravbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te6ravbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:label-sharp" /></template>
