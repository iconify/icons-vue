<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii217uehi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii217uehi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chess-queen" /></template>
