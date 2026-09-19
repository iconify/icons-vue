<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9g86ihie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9g86ihie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:basket" /></template>
