<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_2u1ybfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_2u1ybfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrowed" /></template>
