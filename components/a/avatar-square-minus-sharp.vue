<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h74p_acgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h74p_acgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-square-minus-sharp" /></template>
