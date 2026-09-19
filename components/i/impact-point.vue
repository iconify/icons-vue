<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1a9i0b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1a9i0b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:impact-point" /></template>
