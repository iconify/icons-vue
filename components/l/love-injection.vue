<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-w0-5vki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-w0-5vki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:love-injection" /></template>
