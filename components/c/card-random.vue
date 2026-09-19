<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7k6u3b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7k6u3b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-random" /></template>
