<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sym8z-b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sym8z-b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-search-corner-round" /></template>
