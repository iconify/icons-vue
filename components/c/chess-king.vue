<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsje7487x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fsje7487x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chess-king" /></template>
