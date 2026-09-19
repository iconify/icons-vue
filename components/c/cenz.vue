<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is__0acte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="is__0acte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cenz" /></template>
