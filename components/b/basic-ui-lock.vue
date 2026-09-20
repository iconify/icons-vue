<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb2prubva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mb2prubva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-lock" /></template>
