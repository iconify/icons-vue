<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijyvnplua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ijyvnplua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-hand-shield" /></template>
