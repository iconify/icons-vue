<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1v__7tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kd1v__7tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beer-stein" /></template>
