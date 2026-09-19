<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox0bity7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ox0bity7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:anthem" /></template>
