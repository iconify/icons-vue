<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjc9fdfhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjc9fdfhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:luggage" /></template>
