<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6fqfab6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o6fqfab6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-move-flat" /></template>
