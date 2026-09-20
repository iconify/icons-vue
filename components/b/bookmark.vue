<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu7zv7b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu7zv7b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:bookmark" /></template>
