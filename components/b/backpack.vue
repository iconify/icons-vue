<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnoc_cc4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnoc_cc4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:backpack" /></template>
