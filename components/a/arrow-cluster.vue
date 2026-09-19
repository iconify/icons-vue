<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cytbo59vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cytbo59vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrow-cluster" /></template>
