<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3tol2bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3tol2bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bacon" /></template>
