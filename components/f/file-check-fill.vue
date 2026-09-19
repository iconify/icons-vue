<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u54k7obiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u54k7obiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-check-fill" /></template>
