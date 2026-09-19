<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op484abqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="op484abqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cloud-download" /></template>
