<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ttx_b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9ttx_b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-009" /></template>
