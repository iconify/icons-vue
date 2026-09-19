<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg3ro6b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pg3ro6b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battery-minus" /></template>
