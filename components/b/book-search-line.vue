<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caph1n78r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caph1n78r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-search-line" /></template>
