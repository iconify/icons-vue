<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-9o316jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k-9o316jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-expand-flat" /></template>
