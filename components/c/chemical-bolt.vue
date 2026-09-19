<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzwd4pktt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzwd4pktt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chemical-bolt" /></template>
