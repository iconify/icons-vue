<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kic_o7bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kic_o7bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ground-sprout" /></template>
