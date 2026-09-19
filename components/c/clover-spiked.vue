<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hibq6ccco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hibq6ccco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clover-spiked" /></template>
