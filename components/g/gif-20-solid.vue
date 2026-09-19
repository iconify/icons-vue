<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arcph36co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="arcph36co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:gif-20-solid" /></template>
