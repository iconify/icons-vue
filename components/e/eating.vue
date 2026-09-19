<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utb9ql0jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="utb9ql0jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eating" /></template>
