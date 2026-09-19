<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0m8mmivq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0m8mmivq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hill-fort" /></template>
