<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiq7q7toc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tiq7q7toc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clothespin" /></template>
