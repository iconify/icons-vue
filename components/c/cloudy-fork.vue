<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb3sqvbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fb3sqvbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cloudy-fork" /></template>
