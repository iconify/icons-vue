<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kscnyxbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kscnyxbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burning-round-shot" /></template>
