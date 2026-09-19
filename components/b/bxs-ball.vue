<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej4l518vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej4l518vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-ball" /></template>
