<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3fvxkb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3fvxkb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cassowary-head" /></template>
