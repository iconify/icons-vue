<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqyi5614b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqyi5614b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cast" /></template>
