<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1oyp3b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f1oyp3b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:braille" /></template>
