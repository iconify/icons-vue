<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f09ud6upv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f09ud6upv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-text-fill" /></template>
