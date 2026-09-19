<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjm9yabjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjm9yabjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cardboard-box-closed" /></template>
