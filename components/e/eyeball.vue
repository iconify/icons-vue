<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4g2bi8-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4g2bi8-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eyeball" /></template>
