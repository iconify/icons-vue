<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajb6qbcvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajb6qbcvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dart" /></template>
