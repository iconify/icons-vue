<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7ge6771m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k7ge6771m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jelly-beans" /></template>
