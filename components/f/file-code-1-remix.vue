<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgvc7ymii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fgvc7ymii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:file-code-1-remix" /></template>
