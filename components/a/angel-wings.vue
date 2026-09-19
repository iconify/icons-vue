<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue0vf3bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue0vf3bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:angel-wings" /></template>
