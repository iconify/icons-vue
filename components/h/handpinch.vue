<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdh9m0b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="gdh9m0b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handpinch" /></template>
