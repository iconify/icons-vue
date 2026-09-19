<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyy7pdbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyy7pdbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fairy" /></template>
