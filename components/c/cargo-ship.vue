<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky_qdhb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ky_qdhb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cargo-ship" /></template>
