<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cemynpbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cemynpbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:english-rectangle-filled" /></template>
