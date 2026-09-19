<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcwwytb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcwwytb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-saber" /></template>
