<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmnizdl7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmnizdl7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar-circle-x" /></template>
