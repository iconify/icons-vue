<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe51tmlyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe51tmlyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:interleaved-arrows" /></template>
