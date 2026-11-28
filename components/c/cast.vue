<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo_x69yli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo_x69yli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cast" /></template>
