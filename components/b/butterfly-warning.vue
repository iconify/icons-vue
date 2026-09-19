<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q010x0b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q010x0b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:butterfly-warning" /></template>
