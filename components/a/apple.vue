<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyu-_xuoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pyu-_xuoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:apple" /></template>
