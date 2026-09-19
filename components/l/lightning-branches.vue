<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xklh-8bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xklh-8bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-branches" /></template>
