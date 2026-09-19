<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg4sf4mbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fg4sf4mbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bank" /></template>
