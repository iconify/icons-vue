<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sekq7wn5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sekq7wn5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossed-pistols" /></template>
