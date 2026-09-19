<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7kat_uwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7kat_uwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:log" /></template>
