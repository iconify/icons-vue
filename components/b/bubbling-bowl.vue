<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy08vfjrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cy08vfjrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bubbling-bowl" /></template>
