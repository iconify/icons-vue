<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5w_rjbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5w_rjbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-ace-spades" /></template>
