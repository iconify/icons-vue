<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twnv2zbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="twnv2zbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cz-skorpion" /></template>
