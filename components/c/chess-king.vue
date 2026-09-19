<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqtd8hbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="uqtd8hbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chess-king" /></template>
