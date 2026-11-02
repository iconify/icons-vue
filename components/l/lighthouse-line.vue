<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdi7fsh1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdi7fsh1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lighthouse-line" /></template>
