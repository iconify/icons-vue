<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpe525bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kpe525bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:claw-string" /></template>
