<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0r6-xtig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":610,"height":840};
const content = `<path class="a0r6-xtig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:drop" /></template>
