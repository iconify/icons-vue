<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/figfzkctn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="figfzkctn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-beats" /></template>
