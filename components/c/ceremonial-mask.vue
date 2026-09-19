<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_-10o11k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k_-10o11k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ceremonial-mask" /></template>
