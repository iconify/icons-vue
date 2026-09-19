<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he2e8je9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="he2e8je9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:curly-wing" /></template>
