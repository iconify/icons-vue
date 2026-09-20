<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeo5czbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oeo5czbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:image-saturation-solid" /></template>
