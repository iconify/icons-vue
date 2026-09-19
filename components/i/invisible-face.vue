<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3o1v-b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3o1v-b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:invisible-face" /></template>
