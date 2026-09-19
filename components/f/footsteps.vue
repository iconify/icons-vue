<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c42891b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c42891b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:footsteps" /></template>
