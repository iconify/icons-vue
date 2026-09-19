<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4s5k1myl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4s5k1myl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bastet" /></template>
