<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw7et_bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw7et_bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-094" /></template>
