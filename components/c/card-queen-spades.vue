<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akcv2kb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="akcv2kb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-queen-spades" /></template>
