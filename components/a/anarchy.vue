<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyc9_1b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyc9_1b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:anarchy" /></template>
