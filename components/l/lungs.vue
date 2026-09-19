<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ispsy3v4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ispsy3v4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lungs" /></template>
