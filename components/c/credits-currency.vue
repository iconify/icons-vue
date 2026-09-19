<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sawy8pb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sawy8pb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:credits-currency" /></template>
