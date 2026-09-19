<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkk216bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkk216bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-008" /></template>
