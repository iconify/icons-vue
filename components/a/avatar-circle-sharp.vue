<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0y80gtpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0y80gtpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-circle-sharp" /></template>
