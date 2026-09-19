<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay3y2jkpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ay3y2jkpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eyepatch" /></template>
