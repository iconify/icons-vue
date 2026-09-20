<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmogvib1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hmogvib1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:eraser" /></template>
