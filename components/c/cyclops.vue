<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlz96e2cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wlz96e2cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cyclops" /></template>
