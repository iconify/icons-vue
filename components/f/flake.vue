<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t31b8acbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t31b8acbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flake" /></template>
