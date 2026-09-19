<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopl69-zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gopl69-zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frog-prince" /></template>
