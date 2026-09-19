<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak12ijehf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak12ijehf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:alien-stare" /></template>
