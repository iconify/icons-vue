<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce5wpgb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce5wpgb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clubs-line" /></template>
