<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxiji_sdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dxiji_sdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-text" /></template>
