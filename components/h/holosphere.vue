<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u23o9ub-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u23o9ub-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:holosphere" /></template>
