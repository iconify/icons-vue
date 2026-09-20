<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rph157bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rph157bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:contact-book-solid" /></template>
