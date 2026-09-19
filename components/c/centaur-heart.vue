<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3e0tcciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3e0tcciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:centaur-heart" /></template>
