<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w32j58bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w32j58bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:delete-1-flat" /></template>
