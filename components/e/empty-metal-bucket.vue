<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppq6b8bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppq6b8bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:empty-metal-bucket" /></template>
