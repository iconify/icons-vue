<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myi4758lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="myi4758lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-7-clubs" /></template>
