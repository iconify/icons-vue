<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hskyx7mww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hskyx7mww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bear-face" /></template>
