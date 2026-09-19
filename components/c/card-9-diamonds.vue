<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y05w8bbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y05w8bbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-9-diamonds" /></template>
