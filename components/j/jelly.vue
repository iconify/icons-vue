<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dalk1vyav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dalk1vyav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jelly" /></template>
