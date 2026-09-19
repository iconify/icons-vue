<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpf6b1bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpf6b1bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:imp-laugh" /></template>
