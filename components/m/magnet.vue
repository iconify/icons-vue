<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6_f13bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k6_f13bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magnet" /></template>
