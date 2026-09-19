<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs_5vtbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs_5vtbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:circle-claws" /></template>
