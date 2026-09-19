<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4rxvqb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g4rxvqb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dock" /></template>
