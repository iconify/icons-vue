<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8s3wy4eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8s3wy4eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:divert" /></template>
