<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1c5jzgok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z1c5jzgok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ammonite" /></template>
