<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7_ctwb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m7_ctwb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:camp-cooking-pot" /></template>
