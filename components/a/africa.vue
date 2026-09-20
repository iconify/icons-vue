<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx07y-bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hx07y-bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:africa" /></template>
