<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc71ixbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc71ixbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-047" /></template>
