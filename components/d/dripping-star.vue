<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqzfn4-ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqzfn4-ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dripping-star" /></template>
