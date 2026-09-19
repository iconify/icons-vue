<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnde1pb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="fnde1pb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:gnss" /></template>
