<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a419sp39j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a419sp39j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flat-tire" /></template>
