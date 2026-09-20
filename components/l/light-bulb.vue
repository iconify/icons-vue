<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mggnccc9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mggnccc9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:light-bulb" /></template>
