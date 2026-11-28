<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5r4arjet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5r4arjet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book-search" /></template>
