<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie3otbb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie3otbb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dream-catcher" /></template>
