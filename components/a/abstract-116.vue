<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic7o1nb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ic7o1nb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-116" /></template>
