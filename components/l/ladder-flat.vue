<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj6a17ihb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tj6a17ihb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:ladder-flat" /></template>
