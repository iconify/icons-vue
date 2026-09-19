<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb670dbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mb670dbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chess-queen" /></template>
