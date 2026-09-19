<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqdwd_bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqdwd_bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dunce-cap" /></template>
