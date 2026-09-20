<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rowc7b8ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rowc7b8ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kodular" /></template>
