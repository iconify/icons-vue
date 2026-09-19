<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_o5xl9_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_o5xl9_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bloody-stash" /></template>
