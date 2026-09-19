<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quv36cb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="quv36cb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bison" /></template>
