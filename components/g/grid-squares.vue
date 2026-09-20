<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odawy8e3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="odawy8e3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:grid-squares" /></template>
