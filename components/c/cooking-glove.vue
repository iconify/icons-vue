<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwizefb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wwizefb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cooking-glove" /></template>
