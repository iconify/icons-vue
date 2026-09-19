<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptvz3z25y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ptvz3z25y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-5-hearts" /></template>
