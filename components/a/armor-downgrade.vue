<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei7q5jb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ei7q5jb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armor-downgrade" /></template>
