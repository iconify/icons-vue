<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kepe8c3qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kepe8c3qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chestnut-leaf" /></template>
