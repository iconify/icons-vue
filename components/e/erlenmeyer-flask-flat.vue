<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir9vx3bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ir9vx3bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:erlenmeyer-flask-flat" /></template>
