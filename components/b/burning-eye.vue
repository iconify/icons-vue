<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue0jvth5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue0jvth5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burning-eye" /></template>
