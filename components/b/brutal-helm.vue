<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nly-8rbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nly-8rbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brutal-helm" /></template>
