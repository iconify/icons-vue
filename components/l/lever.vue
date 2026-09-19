<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4r5_k7pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4r5_k7pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lever" /></template>
