<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gniy5bk_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gniy5bk_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:logic-gate-not" /></template>
