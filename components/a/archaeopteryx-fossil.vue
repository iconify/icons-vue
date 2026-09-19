<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm699vahj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hm699vahj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:archaeopteryx-fossil" /></template>
