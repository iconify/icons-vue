<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw3s8g7rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tw3s8g7rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling-star" /></template>
