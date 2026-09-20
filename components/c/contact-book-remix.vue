<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1-n18b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i1-n18b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:contact-book-remix" /></template>
