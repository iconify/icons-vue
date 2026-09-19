<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot-8tac3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ot-8tac3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:divided-spiral" /></template>
