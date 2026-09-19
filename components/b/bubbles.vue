<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayd73xbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ayd73xbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bubbles" /></template>
