<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t58isqm6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t58isqm6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bracer" /></template>
