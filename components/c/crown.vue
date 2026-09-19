<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht0r95bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ht0r95bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crown" /></template>
