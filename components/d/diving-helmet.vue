<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwzz2zy_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwzz2zy_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diving-helmet" /></template>
