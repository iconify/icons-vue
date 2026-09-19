<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by2_5qb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="by2_5qb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:floating-platforms" /></template>
