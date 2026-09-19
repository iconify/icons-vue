<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ern829bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ern829bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-cream-scoop" /></template>
