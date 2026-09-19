<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9jz7db7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="i9jz7db7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:compress" /></template>
