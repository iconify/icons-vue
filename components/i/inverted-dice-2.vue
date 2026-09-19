<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kferin2yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kferin2yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inverted-dice-2" /></template>
