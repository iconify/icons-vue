<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz50gn0rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz50gn0rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery" /></template>
