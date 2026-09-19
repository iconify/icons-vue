<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auj86-bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="auj86-bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:double-face-mask" /></template>
