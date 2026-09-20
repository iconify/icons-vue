<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czrydabio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czrydabio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikimedia-discovery" /></template>
