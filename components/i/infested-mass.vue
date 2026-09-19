<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxm9r3d5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxm9r3d5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:infested-mass" /></template>
