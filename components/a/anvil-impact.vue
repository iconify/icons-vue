<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd1w1xrrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd1w1xrrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:anvil-impact" /></template>
