<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8xjub8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="es8xjub8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:calm-face-in-circle" /></template>
