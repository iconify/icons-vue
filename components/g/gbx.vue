<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwhjj7i3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dwhjj7i3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gbx" /></template>
