<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdq5wv8mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gdq5wv8mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:btg" /></template>
