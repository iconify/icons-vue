<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me46gtb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="me46gtb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:laravel" /></template>
