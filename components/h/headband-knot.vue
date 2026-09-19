<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf_12gmma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf_12gmma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:headband-knot" /></template>
