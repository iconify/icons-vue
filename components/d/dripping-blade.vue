<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwzq_qbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwzq_qbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dripping-blade" /></template>
