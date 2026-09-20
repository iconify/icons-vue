<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y10q4sjml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y10q4sjml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:bluetooth-flat" /></template>
