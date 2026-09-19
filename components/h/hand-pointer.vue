<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcdx9-l-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="lcdx9-l-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-pointer" /></template>
