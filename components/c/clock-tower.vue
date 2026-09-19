<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks7t_sbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ks7t_sbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clock-tower" /></template>
