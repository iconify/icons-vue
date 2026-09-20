<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vubcf06gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vubcf06gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:close-square-light" /></template>
