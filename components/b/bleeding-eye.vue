<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzh3qpetg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzh3qpetg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bleeding-eye" /></template>
