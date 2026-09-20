<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4og4digd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y4og4digd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:image-blur-remix" /></template>
