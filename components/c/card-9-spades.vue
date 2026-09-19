<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jope4zbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jope4zbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-9-spades" /></template>
