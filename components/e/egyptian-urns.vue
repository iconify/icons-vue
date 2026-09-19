<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5qjvab8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5qjvab8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:egyptian-urns" /></template>
