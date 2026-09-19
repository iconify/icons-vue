<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfjone-3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="gfjone-3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:eraser" /></template>
