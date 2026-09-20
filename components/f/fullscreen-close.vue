<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7wlqbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7wlqbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:fullscreen-close" /></template>
