<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f15_xqbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f15_xqbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossed-claws" /></template>
