<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_bmn1bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_bmn1bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:erlenmeyer" /></template>
