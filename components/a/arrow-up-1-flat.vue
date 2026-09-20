<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-dv-5xcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p-dv-5xcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-up-1-flat" /></template>
