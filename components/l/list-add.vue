<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktj9py5wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ktj9py5wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:list-add" /></template>
