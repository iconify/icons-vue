<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl_0t8b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gl_0t8b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bsv" /></template>
