<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8-fmougp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8-fmougp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire" /></template>
