<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_s6b-ete.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_s6b-ete"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:berries-bowl" /></template>
