<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7vvkyp7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q7vvkyp7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-add" /></template>
