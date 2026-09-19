<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x36c-ssbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x36c-ssbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:injustice" /></template>
