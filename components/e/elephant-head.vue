<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_prz6bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_prz6bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:elephant-head" /></template>
