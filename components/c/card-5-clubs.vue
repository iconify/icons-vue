<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isfks3eqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isfks3eqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-5-clubs" /></template>
