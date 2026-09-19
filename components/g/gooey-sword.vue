<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6hmgobkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6hmgobkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gooey-sword" /></template>
