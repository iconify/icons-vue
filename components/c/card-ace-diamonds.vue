<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gof7yqdxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gof7yqdxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-ace-diamonds" /></template>
