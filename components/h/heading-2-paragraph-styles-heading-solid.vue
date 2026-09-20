<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8t4l7sis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w8t4l7sis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heading-2-paragraph-styles-heading-solid" /></template>
