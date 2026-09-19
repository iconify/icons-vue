<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4fb5ehck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4fb5ehck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-ring" /></template>
