<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usyesbc6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="usyesbc6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:invisible-2-flat" /></template>
