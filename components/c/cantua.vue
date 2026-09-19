<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klpf-zbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klpf-zbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cantua" /></template>
