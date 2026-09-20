<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d246sqzmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d246sqzmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:file-add-alternate" /></template>
