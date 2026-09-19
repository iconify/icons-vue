<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n42ahib7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n42ahib7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chakram" /></template>
