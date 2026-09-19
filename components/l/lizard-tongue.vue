<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa584bojz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fa584bojz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lizard-tongue" /></template>
