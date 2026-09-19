<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf5msobie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf5msobie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fried-fish" /></template>
