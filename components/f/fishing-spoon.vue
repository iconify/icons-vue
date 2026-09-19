<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88s3pb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t88s3pb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fishing-spoon" /></template>
