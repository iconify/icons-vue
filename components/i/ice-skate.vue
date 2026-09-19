<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlamg4bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hlamg4bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-skate" /></template>
