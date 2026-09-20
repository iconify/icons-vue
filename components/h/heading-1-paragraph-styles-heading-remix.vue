<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-rz6hkhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s-rz6hkhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heading-1-paragraph-styles-heading-remix" /></template>
