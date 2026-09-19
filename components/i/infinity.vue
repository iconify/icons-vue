<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6l8o5b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6l8o5b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:infinity" /></template>
