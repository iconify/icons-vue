<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzw5ddcwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzw5ddcwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lab-coat" /></template>
