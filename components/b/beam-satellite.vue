<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ax9-_0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q4ax9-_0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beam-satellite" /></template>
