<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l27e00btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="l27e00btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:closed-access-square" /></template>
