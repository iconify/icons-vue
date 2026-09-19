<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6yol1phm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6yol1phm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hedgehog" /></template>
