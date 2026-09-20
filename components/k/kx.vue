<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r--r74bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r--r74bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kx" /></template>
