<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6l_umb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l6l_umb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:corset" /></template>
