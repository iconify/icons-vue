<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtsz6d8hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jtsz6d8hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-5-spades" /></template>
