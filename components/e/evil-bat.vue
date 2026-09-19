<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o44n3gbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o44n3gbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-bat" /></template>
