<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir73gyqfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir73gyqfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-heart-solid" /></template>
