<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afw2xcz8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afw2xcz8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-pick" /></template>
