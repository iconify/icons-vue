<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du2qh3bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="du2qh3bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:html-five-remix" /></template>
