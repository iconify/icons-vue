<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf03ylb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf03ylb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-2-fill" /></template>
