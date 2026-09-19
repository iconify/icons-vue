<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upq_ys5ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="upq_ys5ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:compass" /></template>
