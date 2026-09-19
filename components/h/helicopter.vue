<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsbb90io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlsbb90io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:helicopter" /></template>
