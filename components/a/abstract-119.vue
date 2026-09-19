<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdb3dobzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zdb3dobzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-119" /></template>
