<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x77uurkxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x77uurkxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heavy-thorny-triskelion" /></template>
