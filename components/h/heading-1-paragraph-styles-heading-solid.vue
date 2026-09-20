<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6sywuhsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j6sywuhsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heading-1-paragraph-styles-heading-solid" /></template>
