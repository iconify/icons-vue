<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvhlhhovd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tvhlhhovd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:image-saturation-vertical-remix" /></template>
