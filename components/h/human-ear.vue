<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhfeimbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhfeimbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:human-ear" /></template>
