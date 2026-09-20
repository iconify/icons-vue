<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9rv8y8ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9rv8y8ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-s-circle" /></template>
