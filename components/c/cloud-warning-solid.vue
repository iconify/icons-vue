<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-dj6j5tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e-dj6j5tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cloud-warning-solid" /></template>
