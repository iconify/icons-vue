<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_o76b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_o76b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-search-fill-round" /></template>
