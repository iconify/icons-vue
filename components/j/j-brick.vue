<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lor2j1w8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lor2j1w8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:j-brick" /></template>
