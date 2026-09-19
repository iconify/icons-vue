<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja5en4bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ja5en4bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-flag" /></template>
