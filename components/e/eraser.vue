<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-gdye2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g8-gdye2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:eraser" /></template>
