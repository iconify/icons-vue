<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_na02-yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_na02-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:apc" /></template>
