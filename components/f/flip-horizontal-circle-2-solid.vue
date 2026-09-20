<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me7lfxbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="me7lfxbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:flip-horizontal-circle-2-solid" /></template>
