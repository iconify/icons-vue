<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ypnxbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4ypnxbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:circular-saw" /></template>
