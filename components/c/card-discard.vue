<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8nsw9brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8nsw9brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-discard" /></template>
