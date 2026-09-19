<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq0j-ab4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nq0j-ab4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:canadian-goose" /></template>
