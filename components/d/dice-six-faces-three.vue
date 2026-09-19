<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrcn_602m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrcn_602m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-six-faces-three" /></template>
