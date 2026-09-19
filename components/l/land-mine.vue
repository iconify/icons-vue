<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_g-0b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec_g-0b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:land-mine" /></template>
