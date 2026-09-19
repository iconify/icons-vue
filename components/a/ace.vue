<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dexi62w-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dexi62w-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ace" /></template>
