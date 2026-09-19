<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogq8z8wpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogq8z8wpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:assassin-pocket" /></template>
