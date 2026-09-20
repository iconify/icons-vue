<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isz6hd-im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="isz6hd-im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ciencia-vitae-square" /></template>
