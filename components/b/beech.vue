<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf14bmjhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wf14bmjhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beech" /></template>
