<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqs0mcclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqs0mcclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cut-palm" /></template>
