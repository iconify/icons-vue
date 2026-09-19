<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6yglcc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6yglcc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:guitar-head" /></template>
