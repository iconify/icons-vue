<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blzwy-b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blzwy-b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-8-clubs" /></template>
