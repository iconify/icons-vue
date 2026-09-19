<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5b42eb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5b42eb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inverted-dice-5" /></template>
