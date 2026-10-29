<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku9zw5_gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku9zw5_gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crayon-solid" /></template>
