<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp-xl0bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tp-xl0bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:empty-hourglass" /></template>
