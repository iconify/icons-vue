<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd9zgnr0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd9zgnr0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:archive-research" /></template>
